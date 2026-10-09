<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvli3kbsk.css';
import '../../css/j/j2_5lrbxi.css';
import '../../css/p/pj0row0jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pvli3kbsk"/><path class="j2_5lrbxi"/><path class="pj0row0jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kite-48-bold" {...props}></Icon>
