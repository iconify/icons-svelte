<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6gmxpbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s6gmxpbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:exclamation-solid" {...props}></Icon>
