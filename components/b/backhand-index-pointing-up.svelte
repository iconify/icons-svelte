<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnv4d6brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pnv4d6brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:backhand-index-pointing-up" {...props}></Icon>
