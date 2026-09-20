<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_beh8btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w_beh8btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rack-ipc-fail" {...props}></Icon>
