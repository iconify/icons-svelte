<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qyybdpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7qyybdpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:braille" {...props}></Icon>
