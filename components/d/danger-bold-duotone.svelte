<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qe0am95yg.css';
import '../../css/v/vzgygcepj.css';
import '../../css/j/jwj5s6brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qe0am95yg"/><path class="vzgygcepj"/><path class="jwj5s6brs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-bold-duotone" {...props}></Icon>
