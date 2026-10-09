<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pixuu6bja.css';
import '../../css/q/qlh3x2h3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pixuu6bja"/><path class="qlh3x2h3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-48" {...props}></Icon>
