<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i80f-5bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i80f-5bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dagu-dark" {...props}></Icon>
