<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj166yu5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zj166yu5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-up-two-filled" {...props}></Icon>
