<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjcp39i-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pjcp39i-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gitkraken-wordmark" {...props}></Icon>
