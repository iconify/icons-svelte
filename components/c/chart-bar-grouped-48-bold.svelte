<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8u9mrbde.css';
import '../../css/y/ygsi-xb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8u9mrbde"/><path class="ygsi-xb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-grouped-48-bold" {...props}></Icon>
