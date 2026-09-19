<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mujcmz6vw.css';
import '../../css/q/q-tflgzje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mujcmz6vw"/><path class="q-tflgzje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-up-circle-outline" {...props}></Icon>
