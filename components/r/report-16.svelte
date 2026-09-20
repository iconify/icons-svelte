<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb75cm3nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wb75cm3nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:report-16" {...props}></Icon>
