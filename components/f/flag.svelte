<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm_xmx2dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pm_xmx2dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flag" {...props}></Icon>
