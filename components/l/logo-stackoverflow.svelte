<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpbhyqbff.css';
import '../../css/j/jl37fgbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpbhyqbff"/><path class="jl37fgbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-stackoverflow" {...props}></Icon>
