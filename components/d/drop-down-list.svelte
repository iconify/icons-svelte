<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/d/d8561dbcl.css';
import '../../css/s/sur6g4xqv.css';
import '../../css/r/rw4ic0bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="d8561dbcl"/><path class="sur6g4xqv"/><path class="rw4ic0bsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:drop-down-list" {...props}></Icon>
