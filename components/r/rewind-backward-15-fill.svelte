<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo7izzb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo7izzb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-15-fill" {...props}></Icon>
