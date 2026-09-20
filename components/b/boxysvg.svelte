<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrrdjo_kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrrdjo_kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:boxysvg" {...props}></Icon>
