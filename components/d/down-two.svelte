<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbgytubxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vbgytubxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:down-two" {...props}></Icon>
