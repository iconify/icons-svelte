<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqe_kssen.css';
import '../../css/j/jl4dq47bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pqe_kssen"/><path class="jl4dq47bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flame-48" {...props}></Icon>
