<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fept4eb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fept4eb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:flyway-wordmark" {...props}></Icon>
