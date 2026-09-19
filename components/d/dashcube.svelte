<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n71rvzb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n71rvzb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:dashcube" {...props}></Icon>
