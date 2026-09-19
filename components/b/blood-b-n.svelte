<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ivgjj6_5c.css';
import '../../css/r/rxaqa1ufk.css';
import '../../css/k/ks-hkhxjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ivgjj6_5c"/><path class="rxaqa1ufk"/><path clip-rule="evenodd" class="ks-hkhxjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-b-n" {...props}></Icon>
