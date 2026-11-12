<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc3v_0bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tc3v_0bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:databricks" {...props}></Icon>
