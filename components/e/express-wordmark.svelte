<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doh7t8rwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="doh7t8rwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:express-wordmark" {...props}></Icon>
