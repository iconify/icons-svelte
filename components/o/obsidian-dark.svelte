<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbhi0cbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbhi0cbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obsidian-dark" {...props}></Icon>
