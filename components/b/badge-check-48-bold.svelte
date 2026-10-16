<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si1030bhs.css';
import '../../css/l/lp5-n4bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si1030bhs"/><path class="lp5-n4bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-check-48-bold" {...props}></Icon>
