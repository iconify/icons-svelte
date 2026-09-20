<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/znogc8yyg.css';
import '../../css/g/gafy37gmj.css';
import '../../css/s/s0c6a526o.css';
import '../../css/t/ty9rd6b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="znogc8yyg"/><path class="gafy37gmj"/><path class="s0c6a526o"/><path class="ty9rd6b5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-search-bold" {...props}></Icon>
