<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_e3xfbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b_e3xfbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pfsense-wordmark" {...props}></Icon>
