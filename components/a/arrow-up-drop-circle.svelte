<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt1_pr37r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1_pr37r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-drop-circle" {...props}></Icon>
