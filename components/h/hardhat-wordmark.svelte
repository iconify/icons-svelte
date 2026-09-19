<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_668e8lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x_668e8lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hardhat-wordmark" {...props}></Icon>
