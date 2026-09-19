<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_n2pacdg.css';
import '../../css/d/dh4ihvbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_n2pacdg"/><path class="dh4ihvbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:building-insights-3" {...props}></Icon>
