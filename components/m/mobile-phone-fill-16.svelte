<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtdb2rb_j.css';
import '../../css/d/dmcux5bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="dtdb2rb_j"/><path class="dmcux5bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:mobile-phone-fill-16" {...props}></Icon>
