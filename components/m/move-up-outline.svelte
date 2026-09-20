<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw2pvlb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yw2pvlb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:move-up-outline" {...props}></Icon>
