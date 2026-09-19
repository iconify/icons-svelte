<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5cigt5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="minus-outline"><path class="Vector di5cigt5f" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:minus-outline" {...props}></Icon>
