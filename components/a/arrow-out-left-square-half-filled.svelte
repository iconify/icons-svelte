<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxf1odf7b.css';
import '../../css/s/sgoebkv5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf1odf7b"/><path class="sgoebkv5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-left-square-half-filled" {...props}></Icon>
