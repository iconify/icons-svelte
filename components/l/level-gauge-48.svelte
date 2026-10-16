<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl870bc1m.css';
import '../../css/t/te3lkr3kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jl870bc1m"/><path class="te3lkr3kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:level-gauge-48" {...props}></Icon>
