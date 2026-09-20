<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy38pybef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gy38pybef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-16" {...props}></Icon>
