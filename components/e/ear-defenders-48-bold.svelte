<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6feayb0f.css';
import '../../css/p/pi921jb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v6feayb0f"/><path class="pi921jb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-defenders-48-bold" {...props}></Icon>
