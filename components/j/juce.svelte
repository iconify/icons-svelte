<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-8v9bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ot-8v9bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:juce" {...props}></Icon>
