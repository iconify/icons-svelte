<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdb70jjls.css';
import '../../css/t/tfdzc8bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wdb70jjls"/><path class="tfdzc8bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:or-gate-48" {...props}></Icon>
