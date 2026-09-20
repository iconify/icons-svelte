<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc5w65bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rc5w65bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-data-transfer-solid" {...props}></Icon>
