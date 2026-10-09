<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl6xnzcek.css';
import '../../css/u/u4btp48pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jl6xnzcek"/><path class="u4btp48pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refinery-20" {...props}></Icon>
