<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w04-kacle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w04-kacle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:box-ipc-question" {...props}></Icon>
