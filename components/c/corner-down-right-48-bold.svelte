<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3__hfs6p.css';
import '../../css/z/zvtm7bcct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3__hfs6p"/><path class="zvtm7bcct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-right-48-bold" {...props}></Icon>
