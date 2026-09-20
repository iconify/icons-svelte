<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qggyhabao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qggyhabao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-drawing-dark" {...props}></Icon>
