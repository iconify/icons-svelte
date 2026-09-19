<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/h/h79p7xb_v.css';
import '../../css/j/jiw5t38fp.css';
import '../../css/e/ezm4tij9w.css';
import '../../css/k/kxwi57u2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="h79p7xb_v"/><path class="jiw5t38fp"/><path class="ezm4tij9w"/><path class="kxwi57u2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:code-download" {...props}></Icon>
