<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mi-mpqbpu.css';
import '../../css/i/il17kbbxg.css';
import '../../css/e/ehq3u9bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mi-mpqbpu"/><rect class="il17kbbxg"/><path class="ehq3u9bfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:notepad-text" {...props}></Icon>
