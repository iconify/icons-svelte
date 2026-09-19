<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f27cr3b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f27cr3b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:knockout-wordmark" {...props}></Icon>
