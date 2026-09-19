<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt5z90bty.css';
import '../../css/r/r7co23qft.css';
import '../../css/w/wpnqak87z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt5z90bty"/><path class="r7co23qft"/><path class="wpnqak87z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-code-download" {...props}></Icon>
