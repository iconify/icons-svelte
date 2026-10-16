<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgupoibyg.css';
import '../../css/u/uc3zgsbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="uc3zgsbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aquifer-48" {...props}></Icon>
