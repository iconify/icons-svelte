<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/z/z8rqlrb4w.css';
import '../../css/s/s2p4zacxn.css';
import '../../css/o/oyh43sbch.css';
import '../../css/j/jv5ve3wru.css';
import '../../css/d/d-b4r8g7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="z8rqlrb4w"/><path class="s2p4zacxn"/><path class="oyh43sbch"/><path class="jv5ve3wru"/><path class="d-b4r8g7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:end-time-sort" {...props}></Icon>
