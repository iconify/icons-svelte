<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iol3lcl0r.css';
import '../../css/c/ca0b8gbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="iol3lcl0r"/><path class="ca0b8gbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:gift" {...props}></Icon>
