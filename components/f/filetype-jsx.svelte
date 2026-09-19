<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6_cjb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zr6_cjb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-jsx" {...props}></Icon>
