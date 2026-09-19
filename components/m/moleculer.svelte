<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7bx3lbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o7bx3lbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:moleculer" {...props}></Icon>
