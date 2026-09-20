<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9wr-tufw.css';
import '../../css/b/b_gbm88ug.css';
import '../../css/i/inndkdxao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g class="h9wr-tufw"><path class="b_gbm88ug"/><path class="inndkdxao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:otne" {...props}></Icon>
