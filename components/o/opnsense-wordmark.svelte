<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00c69yzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f00c69yzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opnsense-wordmark" {...props}></Icon>
