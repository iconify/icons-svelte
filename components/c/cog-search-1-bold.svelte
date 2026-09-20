<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv572stwh.css';
import '../../css/n/nee9o4w2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv572stwh"/><path class="nee9o4w2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cog-search-1-bold" {...props}></Icon>
