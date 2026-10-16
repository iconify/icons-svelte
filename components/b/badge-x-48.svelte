<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jha4hptgn.css';
import '../../css/k/ko3mi2bbn.css';
import '../../css/b/bc05qdnjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jha4hptgn"/><path class="ko3mi2bbn"/><path class="bc05qdnjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-x-48" {...props}></Icon>
