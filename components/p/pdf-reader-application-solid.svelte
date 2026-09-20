<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtz-oe5vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qtz-oe5vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pdf-reader-application-solid" {...props}></Icon>
