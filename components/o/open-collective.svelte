<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlq402btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlq402btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open-collective" {...props}></Icon>
