<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgfg79rry.css';
import '../../css/y/y6gza9ttc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lgfg79rry"/><path class="y6gza9ttc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:globe" {...props}></Icon>
