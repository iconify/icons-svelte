<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzr7ecx0m.css';
import '../../css/l/lizp2ibyj.css';
import '../../css/v/vph4g2brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mzr7ecx0m"/><path class="lizp2ibyj"/><path class="vph4g2brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cogs-48-bold" {...props}></Icon>
