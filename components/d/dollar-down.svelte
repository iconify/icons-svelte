<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f46mr-fii.css';
import '../../css/i/ie50nzixu.css';
import '../../css/m/mow89gbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f46mr-fii"/><path class="ie50nzixu"/><path class="mow89gbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dollar-down" {...props}></Icon>
