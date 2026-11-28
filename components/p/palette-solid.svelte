<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i312qdf_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i312qdf_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:palette-solid" {...props}></Icon>
