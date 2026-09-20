<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf42_qb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zf42_qb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:computer-exclamation-outline" {...props}></Icon>
