<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rdk03xjzw.css';
import '../../css/u/u4ubiccdj.css';
import '../../css/t/ts6026b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rdk03xjzw"/><path class="u4ubiccdj"/><path class="ts6026b9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:planet4-duotone" {...props}></Icon>
