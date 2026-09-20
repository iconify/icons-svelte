<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx4qcgl2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx4qcgl2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filesync-light" {...props}></Icon>
