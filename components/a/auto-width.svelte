<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqov3yajq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wqov3yajq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:auto-width" {...props}></Icon>
