<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vobd55u4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="play-outline"><path class="(Stroke) 54 Vector vobd55u4d" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:play-outline" {...props}></Icon>
