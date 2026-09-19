<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5r42tyxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="p5r42tyxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:postgresql" {...props}></Icon>
