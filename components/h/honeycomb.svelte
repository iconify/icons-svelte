<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trtajbcie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="trtajbcie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:honeycomb" {...props}></Icon>
