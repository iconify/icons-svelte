<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkipg-bnu.css';
import '../../css/e/etvxrubdo.css';
import '../../css/j/j_numcn-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tkipg-bnu"/><path class="etvxrubdo"/><path class="j_numcn-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:enhanced-weathering-48" {...props}></Icon>
