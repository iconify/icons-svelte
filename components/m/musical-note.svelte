<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu5pueb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nu5pueb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:musical-note" {...props}></Icon>
