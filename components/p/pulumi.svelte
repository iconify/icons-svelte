<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgp229bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lgp229bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pulumi" {...props}></Icon>
