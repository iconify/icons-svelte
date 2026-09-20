<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj0y3zbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xj0y3zbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:inbox-fill-16" {...props}></Icon>
