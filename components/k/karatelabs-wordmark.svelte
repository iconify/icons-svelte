<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0fv3xb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w0fv3xb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:karatelabs-wordmark" {...props}></Icon>
