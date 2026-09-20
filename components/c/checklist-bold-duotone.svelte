<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yuh3c-bdf.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/h/h_oi-tcog.css';
import '../../css/z/zsdc5-17y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yuh3c-bdf"/><g class="mc2zb0bvp"><path class="h_oi-tcog"/><path class="zsdc5-17y"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:checklist-bold-duotone" {...props}></Icon>
