<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3yjw5q7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v3yjw5q7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opnsense" {...props}></Icon>
