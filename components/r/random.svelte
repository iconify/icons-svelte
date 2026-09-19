<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t38tdl0sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="t38tdl0sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:random" {...props}></Icon>
