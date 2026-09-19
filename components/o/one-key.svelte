<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/s/srwpu7b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><rect class="xhdah4bbl"/><path class="srwpu7b8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:one-key" {...props}></Icon>
