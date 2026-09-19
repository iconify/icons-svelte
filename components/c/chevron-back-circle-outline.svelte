<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-tflgzje.css';
import '../../css/w/wv95f72ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="wv95f72ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-back-circle-outline" {...props}></Icon>
