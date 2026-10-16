<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z76gmk76o.css';
import '../../css/q/qog7c2b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z76gmk76o"/><path class="qog7c2b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-solar-20" {...props}></Icon>
