<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk524nb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rk524nb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:puzzle" {...props}></Icon>
