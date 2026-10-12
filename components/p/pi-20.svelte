<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdqwsub7z.css';
import '../../css/i/iz3j3vbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdqwsub7z"/><path class="iz3j3vbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pi-20" {...props}></Icon>
