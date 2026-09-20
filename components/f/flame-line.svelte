<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgp09xbhr.css';
import '../../css/i/i1tveqj0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgp09xbhr"/><path class="i1tveqj0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flame-line" {...props}></Icon>
