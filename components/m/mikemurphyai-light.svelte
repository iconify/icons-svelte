<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epal7ia0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="epal7ia0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mikemurphyai-light" {...props}></Icon>
