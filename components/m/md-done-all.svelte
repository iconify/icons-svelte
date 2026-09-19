<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrw4_bbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrw4_bbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-done-all" {...props}></Icon>
