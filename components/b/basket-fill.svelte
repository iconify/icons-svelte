<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcp-q-fmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zcp-q-fmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:basket-fill" {...props}></Icon>
