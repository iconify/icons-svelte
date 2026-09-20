<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz0qowrdw.css';
import '../../css/b/bc_xb1bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zz0qowrdw"/><path class="bc_xb1bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:quality-3-16" {...props}></Icon>
