<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnccb1p9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rnccb1p9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-x-mark-16-solid" {...props}></Icon>
