<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi2u0qhkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mi2u0qhkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:dizzy" {...props}></Icon>
