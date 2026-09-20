<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjxa-7b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjxa-7b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-longhorn" {...props}></Icon>
