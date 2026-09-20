<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8qjncb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8qjncb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cloud-done" {...props}></Icon>
