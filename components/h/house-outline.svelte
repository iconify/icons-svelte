<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icl41xlnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icl41xlnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:house-outline" {...props}></Icon>
