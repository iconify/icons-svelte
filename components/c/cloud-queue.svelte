<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ao-hb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ao-hb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-queue" {...props}></Icon>
