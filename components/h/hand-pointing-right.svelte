<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2_50w-9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2_50w-9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-pointing-right" {...props}></Icon>
