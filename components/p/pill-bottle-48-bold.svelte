<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxr2twvpp.css';
import '../../css/e/ebng-2bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cxr2twvpp"/><path class="ebng-2bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-bottle-48-bold" {...props}></Icon>
