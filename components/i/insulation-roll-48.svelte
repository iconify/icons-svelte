<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw2u6puwh.css';
import '../../css/r/r_oqf1inc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yw2u6puwh"/><path class="r_oqf1inc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insulation-roll-48" {...props}></Icon>
