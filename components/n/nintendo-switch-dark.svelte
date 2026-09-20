<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlv355f2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlv355f2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nintendo-switch-dark" {...props}></Icon>
