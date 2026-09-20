<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4jq1x2sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y4jq1x2sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-right-from-left-bracket" {...props}></Icon>
