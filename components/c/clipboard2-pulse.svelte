<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/za0zhmbnj.css';
import '../../css/t/t9kfpgbow.css';
import '../../css/g/g7om-gl3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="za0zhmbnj"/><path class="t9kfpgbow"/><path class="g7om-gl3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard2-pulse" {...props}></Icon>
