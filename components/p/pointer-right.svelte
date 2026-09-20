<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqfn-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kjqfn-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pointer-right" {...props}></Icon>
