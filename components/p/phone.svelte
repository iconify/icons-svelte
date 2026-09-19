<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl84s6vhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="jl84s6vhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:phone" {...props}></Icon>
