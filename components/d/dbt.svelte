<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q284ii8xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q284ii8xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dbt" {...props}></Icon>
