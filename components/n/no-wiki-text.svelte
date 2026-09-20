<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snoq0vy-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="snoq0vy-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:no-wiki-text" {...props}></Icon>
