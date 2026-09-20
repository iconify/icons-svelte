<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/i/ivapdzbmk.css';
import '../../css/w/wb367bb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="ivapdzbmk"/><path class="wb367bb3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fish" {...props}></Icon>
