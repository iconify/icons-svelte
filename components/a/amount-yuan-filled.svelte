<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0g5vt9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bc0g5vt9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-yuan-filled" {...props}></Icon>
