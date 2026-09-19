<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocleddcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="home-outline"><path class="(Stroke) Vector ocleddcfu" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:home-outline" {...props}></Icon>
