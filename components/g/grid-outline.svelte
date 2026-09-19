<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvzo8oh1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="grid-outline"><path class="Vector uvzo8oh1p" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:grid-outline" {...props}></Icon>
