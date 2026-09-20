<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umw_9vdvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umw_9vdvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:file-alt" {...props}></Icon>
