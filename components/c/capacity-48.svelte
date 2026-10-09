<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfx3nk7mg.css';
import '../../css/l/l0v90wbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wfx3nk7mg"/><path class="l0v90wbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacity-48" {...props}></Icon>
