<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zdke2vb7y.css';
import '../../css/w/wy3fqvbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zdke2vb7y"/><path class="wy3fqvbza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:circle-warning" {...props}></Icon>
