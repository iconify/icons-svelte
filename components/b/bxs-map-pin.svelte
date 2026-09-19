<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spzykfbbj.css';
import '../../css/c/cdisl5apr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spzykfbbj"/><path class="cdisl5apr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-map-pin" {...props}></Icon>
