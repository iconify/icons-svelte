<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9mgp746x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g9mgp746x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gate" {...props}></Icon>
