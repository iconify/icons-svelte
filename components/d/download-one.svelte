<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf28uwb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vf28uwb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:download-one" {...props}></Icon>
