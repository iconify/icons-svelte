<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dne2lqbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dne2lqbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-bold" {...props}></Icon>
