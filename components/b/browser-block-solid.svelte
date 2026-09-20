<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4wi_qxjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p4wi_qxjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-block-solid" {...props}></Icon>
