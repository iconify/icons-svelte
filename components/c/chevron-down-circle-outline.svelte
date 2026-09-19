<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-tflgzje.css';
import '../../css/p/png1nf7mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="png1nf7mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-down-circle-outline" {...props}></Icon>
