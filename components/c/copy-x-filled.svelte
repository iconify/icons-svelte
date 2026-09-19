<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuforsmvs.css';
import '../../css/r/r_3yuac4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuforsmvs"/><path class="r_3yuac4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy-x-filled" {...props}></Icon>
