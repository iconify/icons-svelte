<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl_cg_blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zl_cg_blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:mirror-horizontally" {...props}></Icon>
