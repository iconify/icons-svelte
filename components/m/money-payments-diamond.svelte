<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl3lnyh2h.css';
import '../../css/q/q3rs99g9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jl3lnyh2h"/><path class="q3rs99g9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-diamond" {...props}></Icon>
