<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/szx8rvb1l.css';
import '../../css/h/hwkr87bzo.css';
import '../../css/p/pyif0obzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="szx8rvb1l"/><path clip-rule="evenodd" class="hwkr87bzo"/><path class="pyif0obzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:copper-iud" {...props}></Icon>
