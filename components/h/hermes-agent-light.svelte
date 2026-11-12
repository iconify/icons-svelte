<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da8y-n0pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="da8y-n0pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermes-agent-light" {...props}></Icon>
