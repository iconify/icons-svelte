<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp-nd7g4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":496};
const content = `<path class="xp-nd7g4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:fire" {...props}></Icon>
