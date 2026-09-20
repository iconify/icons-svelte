<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u459c10xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u459c10xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-purifier-off" {...props}></Icon>
