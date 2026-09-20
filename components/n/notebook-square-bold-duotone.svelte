<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c4z116bnm.css';
import '../../css/f/ftrssobwy.css';
import '../../css/l/lv9n1n5sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c4z116bnm"/><path class="ftrssobwy"/><path class="lv9n1n5sk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-square-bold-duotone" {...props}></Icon>
