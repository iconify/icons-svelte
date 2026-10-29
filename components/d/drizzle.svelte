<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik3qoab9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ik3qoab9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:drizzle" {...props}></Icon>
