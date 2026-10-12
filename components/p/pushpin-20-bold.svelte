<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktghhy0et.css';
import '../../css/e/ept6rpbfu.css';
import '../../css/g/ga3wfsbxu.css';
import '../../css/v/vz2ceoucx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ktghhy0et"/><path class="ept6rpbfu"/><path class="ga3wfsbxu"/><path class="vz2ceoucx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pushpin-20-bold" {...props}></Icon>
