<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knz6qdp8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="knz6qdp8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:double-arrow-left-outline" {...props}></Icon>
