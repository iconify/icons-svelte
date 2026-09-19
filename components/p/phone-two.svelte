<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/f8eyw1sna.css';
import '../../css/u/u1jc8vaze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="h01tyzbfu"><path class="f8eyw1sna"/><path class="u1jc8vaze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:phone-two" {...props}></Icon>
