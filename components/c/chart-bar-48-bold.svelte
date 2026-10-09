<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8u9mrbde.css';
import '../../css/o/oum-_kb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="oum-_kb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-48-bold" {...props}></Icon>
