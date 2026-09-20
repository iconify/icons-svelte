<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvt68wnkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cvt68wnkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pizza" {...props}></Icon>
