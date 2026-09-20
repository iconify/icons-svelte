<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrjesu85j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrjesu85j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image" {...props}></Icon>
