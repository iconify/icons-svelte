<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skg5yh4xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skg5yh4xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-open-outline" {...props}></Icon>
