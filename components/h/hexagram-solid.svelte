<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajynfcb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ajynfcb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hexagram-solid" {...props}></Icon>
