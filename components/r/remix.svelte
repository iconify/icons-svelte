<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtw6cewip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jtw6cewip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:remix" {...props}></Icon>
