<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0cn4bty.css';
import '../../css/j/j9asqvqjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zg0cn4bty"/><path clip-rule="evenodd" class="j9asqvqjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dot-net-wordmark" {...props}></Icon>
