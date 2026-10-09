<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lstwdq_nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lstwdq_nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-click-48" {...props}></Icon>
