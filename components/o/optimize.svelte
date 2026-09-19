<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/n/n5yt22b6q.css';
import '../../css/r/ro0gdgbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="n5yt22b6q"/><path class="ro0gdgbme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:optimize" {...props}></Icon>
