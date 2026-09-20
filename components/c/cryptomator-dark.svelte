<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w33c8ljfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w33c8ljfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cryptomator-dark" {...props}></Icon>
