<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_6rrccmc.css';
import '../../css/u/ufby2lc1j.css';
import '../../css/x/x-xho5uub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m_6rrccmc"/><path class="ufby2lc1j"/><path class="x-xho5uub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-meter-48-bold" {...props}></Icon>
