<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tktr2s5ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="tktr2s5ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelshield" {...props}></Icon>
