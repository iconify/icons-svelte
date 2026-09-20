<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2swa8bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2swa8bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openziti-light" {...props}></Icon>
