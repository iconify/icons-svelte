<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgqpnubmx.css';
import '../../css/e/e8k7b6bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgqpnubmx"/><path class="e8k7b6bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opengym" {...props}></Icon>
