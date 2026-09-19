<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ujt3mubdv.css';
import '../../css/h/hr5zc9cra.css';
import '../../css/i/ipt0o-xhs.css';
import '../../css/q/q4mcc3b5a.css';
import '../../css/o/ozd8slbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ujt3mubdv"/><path clip-rule="evenodd" class="hr5zc9cra"/><path clip-rule="evenodd" class="ipt0o-xhs"/><path class="q4mcc3b5a"/><path clip-rule="evenodd" class="ozd8slbja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:gift" {...props}></Icon>
