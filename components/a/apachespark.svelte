<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgazg08rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hgazg08rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apachespark" {...props}></Icon>
