<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljxy0pbpp.css';
import '../../css/t/t2peqlb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ljxy0pbpp"/><path class="t2peqlb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-48" {...props}></Icon>
