<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u52m7xbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u52m7xbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:command-48" {...props}></Icon>
