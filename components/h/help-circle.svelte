<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flip2ibmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flip2ibmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:help-circle" {...props}></Icon>
