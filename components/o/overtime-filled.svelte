<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-6d4u1ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n-6d4u1ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:overtime-filled" {...props}></Icon>
