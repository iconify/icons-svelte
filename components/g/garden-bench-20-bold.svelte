<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcgtjcb0f.css';
import '../../css/f/fmoi5vldd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kcgtjcb0f"/><path class="fmoi5vldd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garden-bench-20-bold" {...props}></Icon>
