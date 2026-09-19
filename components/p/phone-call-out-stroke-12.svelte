<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4x29vb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g4x29vb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-out-stroke-12" {...props}></Icon>
