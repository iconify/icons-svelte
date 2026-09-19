<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3b_mmbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="k3b_mmbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hand-up" {...props}></Icon>
