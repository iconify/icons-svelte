<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sofplebhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sofplebhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:quote-16" {...props}></Icon>
