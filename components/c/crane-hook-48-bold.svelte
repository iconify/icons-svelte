<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmwoaz3te.css';
import '../../css/m/m6lmdhbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmwoaz3te"/><path class="m6lmdhbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crane-hook-48-bold" {...props}></Icon>
