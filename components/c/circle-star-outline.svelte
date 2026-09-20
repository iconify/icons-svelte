<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nnc71dbsl.css';
import '../../css/i/imnimkbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="nnc71dbsl"/><path class="imnimkbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-star-outline" {...props}></Icon>
