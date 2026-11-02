<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_2il82l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_2il82l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-line" {...props}></Icon>
