<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajzldfipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ajzldfipa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paper-airplane-16" {...props}></Icon>
