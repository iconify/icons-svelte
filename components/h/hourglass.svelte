<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m99s_db5h.css';
import '../../css/j/jz1kv-49a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":32};
const content = `<g class="cuyn6tgcc"><path class="m99s_db5h"/><path class="jz1kv-49a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:hourglass" {...props}></Icon>
