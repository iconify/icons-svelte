<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juv3elbto.css';
import '../../css/q/q-tflgzje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="juv3elbto"/><path class="q-tflgzje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-undo-circle-outline" {...props}></Icon>
