<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izb9fdczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izb9fdczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy-disc-move" {...props}></Icon>
