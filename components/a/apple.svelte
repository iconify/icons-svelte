<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udxgnlb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="udxgnlb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apple" {...props}></Icon>
