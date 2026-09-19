<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu__y2bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xu__y2bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kubernetes" {...props}></Icon>
