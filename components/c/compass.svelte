<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rpxvvzoag.css';
import '../../css/n/nmcrzeajb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="rpxvvzoag"/><path class="nmcrzeajb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:compass" {...props}></Icon>
