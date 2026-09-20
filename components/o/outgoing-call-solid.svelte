<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lncb9db9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lncb9db9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:outgoing-call-solid" {...props}></Icon>
