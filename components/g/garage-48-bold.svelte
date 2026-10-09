<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op_j2nylw.css';
import '../../css/b/bz0ghpbjx.css';
import '../../css/z/z9_87vb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="op_j2nylw"/><path class="bz0ghpbjx"/><path class="z9_87vb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garage-48-bold" {...props}></Icon>
