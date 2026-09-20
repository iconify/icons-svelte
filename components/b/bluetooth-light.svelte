<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qysbv0mly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qysbv0mly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluetooth-light" {...props}></Icon>
