<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9og61b7p.css';
import '../../css/y/yftb-1bif.css';
import '../../css/p/pzgm9abmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9og61b7p"/><path class="yftb-1bif"/><path class="pzgm9abmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydraulic-cylinder-48" {...props}></Icon>
