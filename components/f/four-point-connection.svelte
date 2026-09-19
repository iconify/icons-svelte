<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7a51mr5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n7a51mr5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:four-point-connection" {...props}></Icon>
