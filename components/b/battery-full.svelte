<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs07zybsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vs07zybsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-full" {...props}></Icon>
