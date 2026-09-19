<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbglvkhxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tbglvkhxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-breakpoint-log-unverified" {...props}></Icon>
