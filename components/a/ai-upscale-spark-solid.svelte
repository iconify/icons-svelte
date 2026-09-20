<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efrdp_bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="efrdp_bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-upscale-spark-solid" {...props}></Icon>
