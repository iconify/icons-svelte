<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjy-gzb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gjy-gzb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-rain-filled" {...props}></Icon>
