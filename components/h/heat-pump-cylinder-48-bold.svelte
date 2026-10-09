<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj475orgc.css';
import '../../css/t/th8tihb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mj475orgc"/><path class="th8tihb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-cylinder-48-bold" {...props}></Icon>
