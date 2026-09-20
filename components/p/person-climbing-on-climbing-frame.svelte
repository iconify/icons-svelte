<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_v_9b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yy_v_9b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-climbing-on-climbing-frame" {...props}></Icon>
