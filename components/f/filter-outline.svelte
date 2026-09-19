<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaf72r2iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="filter-outline"><path class="(Stroke) 38 Vector vaf72r2iq" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:filter-outline" {...props}></Icon>
