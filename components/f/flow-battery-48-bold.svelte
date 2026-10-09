<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9g9dcbtj.css';
import '../../css/l/l45xzzbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v9g9dcbtj"/><path class="l45xzzbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-battery-48-bold" {...props}></Icon>
