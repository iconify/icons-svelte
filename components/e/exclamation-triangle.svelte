<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj5tiwb9w.css';
import '../../css/i/i_m5aoo-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5tiwb9w"/><path class="i_m5aoo-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:exclamation-triangle" {...props}></Icon>
