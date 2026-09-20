<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8bzg1bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8bzg1bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkboxes-blank-circle" {...props}></Icon>
