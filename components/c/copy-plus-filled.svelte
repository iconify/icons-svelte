<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgq_0cbvv.css';
import '../../css/y/yuforsmvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgq_0cbvv"/><path class="yuforsmvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy-plus-filled" {...props}></Icon>
