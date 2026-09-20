<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spdrh7b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spdrh7b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-finder" {...props}></Icon>
