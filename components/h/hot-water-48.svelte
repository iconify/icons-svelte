<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux4uf3b8j.css';
import '../../css/j/jyjbrnbyy.css';
import '../../css/k/ksb4xc21f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ux4uf3b8j"/><path class="jyjbrnbyy"/><path class="ksb4xc21f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-water-48" {...props}></Icon>
