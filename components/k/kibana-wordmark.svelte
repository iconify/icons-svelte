<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpg-z8mwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fpg-z8mwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kibana-wordmark" {...props}></Icon>
