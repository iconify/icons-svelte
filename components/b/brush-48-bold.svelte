<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cywpx4aix.css';
import '../../css/p/pqk-h9_8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cywpx4aix"/><path class="pqk-h9_8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brush-48-bold" {...props}></Icon>
