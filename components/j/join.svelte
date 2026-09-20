<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj8nchxay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qj8nchxay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:join" {...props}></Icon>
