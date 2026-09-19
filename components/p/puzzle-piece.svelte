<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x27cxwf0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x27cxwf0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:puzzle-piece" {...props}></Icon>
