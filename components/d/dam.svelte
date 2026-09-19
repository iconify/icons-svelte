<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxa8gzb9h.css';
import '../../css/z/z6doifb7c.css';
import '../../css/s/sqb-0hb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qxa8gzb9h"/><path class="z6doifb7c"/><path class="sqb-0hb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:dam" {...props}></Icon>
