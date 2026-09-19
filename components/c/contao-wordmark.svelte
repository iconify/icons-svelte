<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0b6c_1tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d0b6c_1tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:contao-wordmark" {...props}></Icon>
