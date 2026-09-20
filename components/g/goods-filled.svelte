<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr38msbnw.css';
import '../../css/h/h_c37acgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nr38msbnw"/><path class="h_c37acgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:goods-filled" {...props}></Icon>
