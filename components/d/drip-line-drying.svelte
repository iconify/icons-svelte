<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r5dwkvbfp.css';
import '../../css/n/nwy6zd9aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r5dwkvbfp"/><path class="nwy6zd9aq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:drip-line-drying" {...props}></Icon>
