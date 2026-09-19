<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou83dy36f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ou83dy36f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:maven-wordmark" {...props}></Icon>
