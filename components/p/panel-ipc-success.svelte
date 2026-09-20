<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkqd1b__q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nkqd1b__q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:panel-ipc-success" {...props}></Icon>
