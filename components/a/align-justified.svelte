<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnlcl2u2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qnlcl2u2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:align-justified" {...props}></Icon>
