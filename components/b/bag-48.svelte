<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb2gho-_w.css';
import '../../css/e/es73ytbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cb2gho-_w"/><path class="es73ytbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-48" {...props}></Icon>
