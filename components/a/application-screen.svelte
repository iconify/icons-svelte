<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b58k86k9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b58k86k9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:application-screen" {...props}></Icon>
