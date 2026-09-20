<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcq9xbc8n.css';
import '../../css/y/y62gldb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qcq9xbc8n"/><path class="y62gldb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-maps" {...props}></Icon>
