<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elpovvbol.css';
import '../../css/o/oc56z-biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="elpovvbol"/><path class="oc56z-biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-half-48" {...props}></Icon>
