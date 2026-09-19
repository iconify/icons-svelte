<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/ohkjqsbos.css';
import '../../css/t/tl2fuobsj.css';
import '../../css/t/t01m3nb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ohkjqsbos"/><circle class="tl2fuobsj"/><path class="t01m3nb-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:receive-limit-outline" {...props}></Icon>
