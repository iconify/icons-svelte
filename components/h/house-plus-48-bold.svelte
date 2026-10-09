<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goie45bfg.css';
import '../../css/q/q87m_jinq.css';
import '../../css/i/it04kcbvr.css';
import '../../css/f/fdlxrep5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goie45bfg"/><path class="q87m_jinq"/><path class="it04kcbvr"/><path class="fdlxrep5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-plus-48-bold" {...props}></Icon>
