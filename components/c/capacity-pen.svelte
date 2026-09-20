<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq_tw-rby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nq_tw-rby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:capacity-pen" {...props}></Icon>
