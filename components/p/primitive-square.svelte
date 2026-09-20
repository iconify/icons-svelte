<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j00zp6u7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="j00zp6u7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:primitive-square" {...props}></Icon>
