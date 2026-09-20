<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pybg2b8cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pybg2b8cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:process-mode-outline" {...props}></Icon>
