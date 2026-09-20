<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz3w198jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cz3w198jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brain-cognitive-remix" {...props}></Icon>
