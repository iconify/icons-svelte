<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g4y3_-fhy.css';
import '../../css/c/c-smvsb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="g4y3_-fhy"/><path clip-rule="evenodd" class="c-smvsb3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:language-20-solid" {...props}></Icon>
