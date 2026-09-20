<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p81p5o69s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p81p5o69s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lore-epic-games" {...props}></Icon>
