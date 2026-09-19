<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvjion_2e.css';
import '../../css/z/z8uj590sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jvjion_2e"/><path class="z8uj590sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-mask" {...props}></Icon>
