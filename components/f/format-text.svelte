<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldk3uy__d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldk3uy__d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text" {...props}></Icon>
