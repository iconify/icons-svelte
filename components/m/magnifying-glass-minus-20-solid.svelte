<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cubpvbc-b.css';
import '../../css/k/kn_yew6ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="cubpvbc-b"/><path clip-rule="evenodd" class="kn_yew6ja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-minus-20-solid" {...props}></Icon>
