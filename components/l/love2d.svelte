<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4hsracca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s4hsracca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:love2d" {...props}></Icon>
