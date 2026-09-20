<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r201o_bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r201o_bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:city-gate-14" {...props}></Icon>
