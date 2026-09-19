<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-mm9atl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bt-mm9atl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:five-ellipses" {...props}></Icon>
