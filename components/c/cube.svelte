<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rup45gbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rup45gbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cube" {...props}></Icon>
