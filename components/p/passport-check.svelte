<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbz25fvgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbz25fvgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:passport-check" {...props}></Icon>
