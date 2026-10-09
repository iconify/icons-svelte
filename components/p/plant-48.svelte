<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpqtu-bsh.css';
import '../../css/c/cq09toq9d.css';
import '../../css/l/lmmaxg6dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cpqtu-bsh"/><path class="cq09toq9d"/><path class="lmmaxg6dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-48" {...props}></Icon>
