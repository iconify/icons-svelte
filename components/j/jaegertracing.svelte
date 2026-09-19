<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq4we08l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uuq4we08l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jaegertracing" {...props}></Icon>
