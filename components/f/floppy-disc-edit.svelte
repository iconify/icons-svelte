<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e43wavbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e43wavbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy-disc-edit" {...props}></Icon>
