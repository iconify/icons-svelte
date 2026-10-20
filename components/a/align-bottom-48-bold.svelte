<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8u9mrbde.css';
import '../../css/z/znkjny7ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="znkjny7ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-bottom-48-bold" {...props}></Icon>
