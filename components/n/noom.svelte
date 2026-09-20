<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jan0qac4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":41,"height":41};
const content = `<path class="jan0qac4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:noom" {...props}></Icon>
