<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w4flpqb4t.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/r/rt40puy8t.css';
import '../../css/m/m8ow94bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w4flpqb4t"/><g class="mc2zb0bvp"><path class="rt40puy8t"/><path class="m8ow94bvr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:city-bold-duotone" {...props}></Icon>
