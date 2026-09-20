<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7dy5yb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7dy5yb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pause-circle-fill" {...props}></Icon>
