<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3zstbr6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w3zstbr6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:blitz" {...props}></Icon>
