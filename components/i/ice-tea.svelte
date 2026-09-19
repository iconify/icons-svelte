<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh9nduq0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qh9nduq0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:ice-tea" {...props}></Icon>
