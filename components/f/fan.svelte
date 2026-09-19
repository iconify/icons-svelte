<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x62avfvkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x62avfvkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fan" {...props}></Icon>
