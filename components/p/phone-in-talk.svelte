<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1z3g4b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="i1z3g4b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-in-talk" {...props}></Icon>
