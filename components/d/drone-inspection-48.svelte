<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6xg2yb8p.css';
import '../../css/k/k86_pzbaj.css';
import '../../css/p/pokp4-yvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w6xg2yb8p"/><path class="k86_pzbaj"/><path class="pokp4-yvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drone-inspection-48" {...props}></Icon>
