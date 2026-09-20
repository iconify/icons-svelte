<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0a7_rbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0a7_rbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-double-16-solid" {...props}></Icon>
