<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmc1bmeor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmc1bmeor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compressed-folder-outline" {...props}></Icon>
