<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjod6gb0n.css';
import '../../css/r/r1303ebjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vjod6gb0n"/><path class="r1303ebjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-budget-48-bold" {...props}></Icon>
