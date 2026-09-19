<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b51-lhp3z.css';
import '../../css/h/h1c-vo8ig.css';
import '../../css/g/gst7bffpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="b51-lhp3z"/><path class="h1c-vo8ig"/><path class="gst7bffpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:eight-key" {...props}></Icon>
