<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp_xfkb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dp_xfkb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nginx" {...props}></Icon>
