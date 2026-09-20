<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs4b4obfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xs4b4obfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nitter" {...props}></Icon>
