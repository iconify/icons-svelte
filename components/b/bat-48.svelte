<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do5a3zb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="do5a3zb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bat-48" {...props}></Icon>
