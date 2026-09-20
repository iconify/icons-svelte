<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luawv7jmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="luawv7jmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bill-4-solid" {...props}></Icon>
