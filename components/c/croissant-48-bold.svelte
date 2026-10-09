<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98iimw6f.css';
import '../../css/j/j9vmdbqgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d98iimw6f"/><path class="j9vmdbqgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:croissant-48-bold" {...props}></Icon>
