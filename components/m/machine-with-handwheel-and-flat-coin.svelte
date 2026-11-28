<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pce7ff9sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pce7ff9sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:machine-with-handwheel-and-flat-coin" {...props}></Icon>
