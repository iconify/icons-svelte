<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkvt3bczz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="figma-logo-outline"><path class="(Stroke) Vector wkvt3bczz" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:figma-logo-outline" {...props}></Icon>
