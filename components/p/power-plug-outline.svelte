<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ce7pzkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ce7pzkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-plug-outline" {...props}></Icon>
