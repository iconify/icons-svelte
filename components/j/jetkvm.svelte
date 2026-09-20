<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeghuabay.css';
import '../../css/g/gb3vxeboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xeghuabay"/><path class="gb3vxeboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jetkvm" {...props}></Icon>
