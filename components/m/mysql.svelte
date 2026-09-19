<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg2igbgln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jg2igbgln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mysql" {...props}></Icon>
