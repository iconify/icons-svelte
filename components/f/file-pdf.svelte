<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jif-fcboa.css';
import '../../css/l/l2t9bkdqd.css';
import '../../css/h/hd1iybcfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jif-fcboa"/><path clip-rule="evenodd" class="l2t9bkdqd"/><path class="hd1iybcfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-pdf" {...props}></Icon>
