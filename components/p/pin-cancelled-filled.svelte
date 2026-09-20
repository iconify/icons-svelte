<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0k__6brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0k__6brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pin-cancelled-filled" {...props}></Icon>
