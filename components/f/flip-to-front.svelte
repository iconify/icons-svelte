<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7-hfdciq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7-hfdciq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:flip-to-front" {...props}></Icon>
