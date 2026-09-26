<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l80i0rb1m.css';
import '../../css/z/z55blto9r.css';
import '../../css/o/oew12fk1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l80i0rb1m"/><path class="z55blto9r"/><path class="oew12fk1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quote-circle-bold-duotone" {...props}></Icon>
