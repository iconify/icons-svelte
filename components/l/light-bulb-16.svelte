<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2c0v3b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f2c0v3b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:light-bulb-16" {...props}></Icon>
