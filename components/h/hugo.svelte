<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyv4_tbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dyv4_tbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hugo" {...props}></Icon>
