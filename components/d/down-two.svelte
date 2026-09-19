<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuchbjbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vuchbjbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:down-two" {...props}></Icon>
