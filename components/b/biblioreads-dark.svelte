<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzvdibb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzvdibb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:biblioreads-dark" {...props}></Icon>
