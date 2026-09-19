<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blh-xxc1n.css';
import '../../css/m/m3q-h-bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="blh-xxc1n"/><path class="m3q-h-bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microphone" {...props}></Icon>
