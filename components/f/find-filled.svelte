<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whi2z9b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="whi2z9b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:find-filled" {...props}></Icon>
