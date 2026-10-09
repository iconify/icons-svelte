<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2bu28b8d.css';
import '../../css/u/uhvsvhbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k2bu28b8d"/><path class="uhvsvhbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fishing-48-bold" {...props}></Icon>
