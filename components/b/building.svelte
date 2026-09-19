<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmsdd661s.css';
import '../../css/k/ktlmm7bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmsdd661s"/><path class="ktlmm7bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:building" {...props}></Icon>
