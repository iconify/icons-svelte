<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68crsbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i68crsbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picture-filled" {...props}></Icon>
