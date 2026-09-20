<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skn_peb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skn_peb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anythingllm-dark" {...props}></Icon>
