<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goie45bfg.css';
import '../../css/q/q87m_jinq.css';
import '../../css/x/x-w4dbc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goie45bfg"/><path class="q87m_jinq"/><path class="x-w4dbc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-alert-48-bold" {...props}></Icon>
