<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goie45bfg.css';
import '../../css/q/q87m_jinq.css';
import '../../css/l/l338p9bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goie45bfg"/><path class="q87m_jinq"/><path class="l338p9bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-check-48-bold" {...props}></Icon>
