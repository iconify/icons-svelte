<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrn60viue.css';
import '../../css/f/fvyubxb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hrn60viue"/><path class="fvyubxb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:junction-box-48-bold" {...props}></Icon>
