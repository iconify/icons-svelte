<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oev4igbca.css';
import '../../css/h/h4u70ccpr.css';
import '../../css/g/gtccdwtex.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oev4igbca"/><path clip-rule="evenodd" class="h4u70ccpr"/><path clip-rule="evenodd" class="gtccdwtex"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:megaphone-circle-off" {...props}></Icon>
