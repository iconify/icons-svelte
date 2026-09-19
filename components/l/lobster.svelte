<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ryg743x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-ryg743x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lobster" {...props}></Icon>
