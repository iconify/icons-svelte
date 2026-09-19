<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpvjsxagt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tpvjsxagt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:anaconda-wordmark" {...props}></Icon>
