<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy7xqk_um.css';
import '../../css/h/hs5ndsbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="hs5ndsbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kanban-48-bold" {...props}></Icon>
