<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jma98wbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jma98wbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy-disc-multiple" {...props}></Icon>
