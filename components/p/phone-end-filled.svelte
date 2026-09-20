<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfgo5ob-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfgo5ob-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-end-filled" {...props}></Icon>
