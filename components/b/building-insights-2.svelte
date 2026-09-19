<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_n2pacdg.css';
import '../../css/s/s_5pz2bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_n2pacdg"/><path class="s_5pz2bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:building-insights-2" {...props}></Icon>
