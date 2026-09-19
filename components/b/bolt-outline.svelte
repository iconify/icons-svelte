<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erx8w3len.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="bolt-outline"><path class="(Stroke) 85 Vector erx8w3len" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:bolt-outline" {...props}></Icon>
