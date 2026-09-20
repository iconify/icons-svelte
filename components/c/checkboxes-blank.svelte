<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8_grb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8_grb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkboxes-blank" {...props}></Icon>
