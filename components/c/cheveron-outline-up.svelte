<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0ih1bnwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z0ih1bnwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:cheveron-outline-up" {...props}></Icon>
