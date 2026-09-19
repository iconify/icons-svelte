<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecyf0d8eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ecyf0d8eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nim-wordmark" {...props}></Icon>
