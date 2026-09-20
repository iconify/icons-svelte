<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyxz16ioe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyxz16ioe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ibeacon" {...props}></Icon>
