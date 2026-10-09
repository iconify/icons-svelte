<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0rmdbc9t.css';
import '../../css/i/ivs89hbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x0rmdbc9t"/><path class="ivs89hbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-check-20-bold" {...props}></Icon>
