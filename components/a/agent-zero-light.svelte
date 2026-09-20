<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usdkizb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usdkizb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agent-zero-light" {...props}></Icon>
