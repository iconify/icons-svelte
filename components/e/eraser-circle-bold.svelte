<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb-js9b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sb-js9b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eraser-circle-bold" {...props}></Icon>
