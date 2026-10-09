<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horcrqbac.css';
import '../../css/r/rhi79hntq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="horcrqbac"/><path class="rhi79hntq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insulation-roll-48-bold" {...props}></Icon>
