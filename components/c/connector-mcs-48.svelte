<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvyr40bsv.css';
import '../../css/g/gm9nibcja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dvyr40bsv"/><path class="gm9nibcja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-mcs-48" {...props}></Icon>
