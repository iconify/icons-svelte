<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkhft_g-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zkhft_g-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flag" {...props}></Icon>
