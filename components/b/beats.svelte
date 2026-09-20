<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfbpbc1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udfbpbc1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:beats" {...props}></Icon>
