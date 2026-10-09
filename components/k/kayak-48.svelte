<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj9ruis6z.css';
import '../../css/j/j1qqfackf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fj9ruis6z"/><path class="j1qqfackf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kayak-48" {...props}></Icon>
