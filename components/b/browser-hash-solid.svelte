<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coyd9vx8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="coyd9vx8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-hash-solid" {...props}></Icon>
