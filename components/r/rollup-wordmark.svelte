<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq-55_boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sq-55_boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rollup-wordmark" {...props}></Icon>
