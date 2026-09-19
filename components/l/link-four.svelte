<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/i/iq51xwu9h.css';
import '../../css/b/be9mrtbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="iq51xwu9h"/><path class="be9mrtbtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:link-four" {...props}></Icon>
