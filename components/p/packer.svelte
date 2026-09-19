<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zroepubiq.css';
import '../../css/z/z-9b709tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zroepubiq"/><path class="z-9b709tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:packer" {...props}></Icon>
