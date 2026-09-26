<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g1fz9lbxt.css';
import '../../css/h/h4rl9styi.css';
import '../../css/u/uruzs8byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g1fz9lbxt"/><path class="h4rl9styi"/><path class="uruzs8byc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-open-bold-duotone" {...props}></Icon>
