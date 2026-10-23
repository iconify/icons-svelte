<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxbjfc6fk.css';
import '../../css/t/t-sghzbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lxbjfc6fk"/><path class="t-sghzbsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactating" {...props}></Icon>
