<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp0s7ccec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp0s7ccec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litlyx" {...props}></Icon>
