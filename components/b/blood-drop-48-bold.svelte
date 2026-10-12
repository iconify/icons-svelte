<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4ifueief.css';
import '../../css/v/v2yg3bceh.css';
import '../../css/w/w762ysbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s4ifueief"/><path class="v2yg3bceh"/><path class="w762ysbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blood-drop-48-bold" {...props}></Icon>
