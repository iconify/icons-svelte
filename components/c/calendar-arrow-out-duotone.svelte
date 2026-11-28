<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b-gd9ibem.css';
import '../../css/r/rnrnfqbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="b-gd9ibem"/><path class="rnrnfqbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-out-duotone" {...props}></Icon>
