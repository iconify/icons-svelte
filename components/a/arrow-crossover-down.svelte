<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9s90sbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x9s90sbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-crossover-down" {...props}></Icon>
