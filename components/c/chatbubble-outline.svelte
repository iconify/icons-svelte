<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smvx7zb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="chatbubble-outline"><path class="(Stroke) 27 Ellipse smvx7zb7y" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:chatbubble-outline" {...props}></Icon>
