<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_i86cclf.css';
import '../../css/a/an8j9_bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h_i86cclf"/><path class="an8j9_bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forward-48-bold" {...props}></Icon>
