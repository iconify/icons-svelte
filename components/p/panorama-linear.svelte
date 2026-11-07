<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j3ccklbsh.css';
import '../../css/t/t2cylssnp.css';
import '../../css/v/va6ug5b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j3ccklbsh"/><path class="t2cylssnp"/><path class="va6ug5b5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-linear" {...props}></Icon>
