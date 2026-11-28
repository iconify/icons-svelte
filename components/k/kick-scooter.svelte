<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl8_86btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl8_86btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:kick-scooter" {...props}></Icon>
