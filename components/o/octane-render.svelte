<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ot-4bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ot-4bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:octane-render" {...props}></Icon>
