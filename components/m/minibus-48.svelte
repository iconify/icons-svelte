<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp02g-bms.css';
import '../../css/t/t_7qy9b-e.css';
import '../../css/r/rviy4nhfj.css';
import '../../css/a/a9jgigbhm.css';
import '../../css/s/sttuocbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fp02g-bms"/><path class="t_7qy9b-e"/><path class="rviy4nhfj"/><path class="a9jgigbhm"/><path class="sttuocbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minibus-48" {...props}></Icon>
