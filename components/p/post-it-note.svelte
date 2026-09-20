<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8vg65w1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8vg65w1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note" {...props}></Icon>
