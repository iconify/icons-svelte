<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szmdkibbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="szmdkibbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paintcan" {...props}></Icon>
