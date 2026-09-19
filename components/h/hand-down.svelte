<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/p/pby3-ccaw.css';
import '../../css/a/aqh3xx5vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="pby3-ccaw"/><path clip-rule="evenodd" class="aqh3xx5vt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:hand-down" {...props}></Icon>
