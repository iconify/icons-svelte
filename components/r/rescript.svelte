<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl9u7obry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jl9u7obry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rescript" {...props}></Icon>
