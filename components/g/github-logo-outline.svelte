<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6o5rl8bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="github-logo-outline"><path class="(Stroke) Vector c6o5rl8bt" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:github-logo-outline" {...props}></Icon>
