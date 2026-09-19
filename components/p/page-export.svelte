<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n58o9b3sw.css';
import '../../css/q/qsljfib0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n58o9b3sw"/><path class="qsljfib0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-export" {...props}></Icon>
