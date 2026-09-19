<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/ftpkt8zyt.css';
import '../../css/f/f2sltbbdx.css';
import '../../css/r/ru9wejb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ftpkt8zyt"/><circle class="f2sltbbdx"/><path class="ru9wejb0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-date-one" {...props}></Icon>
