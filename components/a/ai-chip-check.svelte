<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4ic54bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ic54bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ai-chip-check" {...props}></Icon>
