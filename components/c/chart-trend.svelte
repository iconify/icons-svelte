<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5fi-nhgh.css';
import '../../css/s/s8x-bmb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5fi-nhgh"/><path class="s8x-bmb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chart-trend" {...props}></Icon>
