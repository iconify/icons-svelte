<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbff0lbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbff0lbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:mindmap-list" {...props}></Icon>
