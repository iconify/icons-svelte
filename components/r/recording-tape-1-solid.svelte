<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvkhmp2za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xvkhmp2za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:recording-tape-1-solid" {...props}></Icon>
