<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubic6b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vubic6b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:horizontal-rule-16" {...props}></Icon>
