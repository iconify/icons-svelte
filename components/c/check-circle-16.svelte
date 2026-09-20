<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7zh4ybar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f7zh4ybar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:check-circle-16" {...props}></Icon>
