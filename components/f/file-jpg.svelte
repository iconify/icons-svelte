<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jif-fcboa.css';
import '../../css/n/n30r1sbok.css';
import '../../css/j/j5nytdpoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jif-fcboa"/><path class="n30r1sbok"/><path class="j5nytdpoh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-jpg" {...props}></Icon>
