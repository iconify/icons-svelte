<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo9isi4jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="jo9isi4jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:icecreamalt" {...props}></Icon>
