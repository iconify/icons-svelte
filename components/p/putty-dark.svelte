<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8k7r890n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8k7r890n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:putty-dark" {...props}></Icon>
