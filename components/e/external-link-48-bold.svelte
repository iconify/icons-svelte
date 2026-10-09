<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkc0ul0xf.css';
import '../../css/j/jgs4mub3w.css';
import '../../css/l/led_7kbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jkc0ul0xf"/><path class="jgs4mub3w"/><path class="led_7kbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:external-link-48-bold" {...props}></Icon>
