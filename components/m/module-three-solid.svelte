<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgc3b8bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xgc3b8bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:module-three-solid" {...props}></Icon>
