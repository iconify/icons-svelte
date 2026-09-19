<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv_gh48en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zv_gh48en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mouse2" {...props}></Icon>
