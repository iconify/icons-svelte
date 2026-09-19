<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-uncc2s.css';
import '../../css/z/z33pz2bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ee-uncc2s"/><path class="z33pz2bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fiber" {...props}></Icon>
