<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smiup2bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="smiup2bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:find-outline" {...props}></Icon>
