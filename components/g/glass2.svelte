<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eplhw_nba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eplhw_nba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:glass2" {...props}></Icon>
