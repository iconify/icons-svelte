<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igq7hkbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="igq7hkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:denojs" {...props}></Icon>
