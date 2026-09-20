<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axmd_h3dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axmd_h3dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lvgl" {...props}></Icon>
