<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx937tb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":230,"height":230};
const content = `<path class="xx937tb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:drone-light" {...props}></Icon>
