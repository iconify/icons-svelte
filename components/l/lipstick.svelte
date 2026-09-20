<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/k/ks0qo9bbe.css';
import '../../css/v/vorlg-byp.css';
import '../../css/y/yeb121b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="ks0qo9bbe"/><path class="vorlg-byp"/><path class="yeb121b_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:lipstick" {...props}></Icon>
