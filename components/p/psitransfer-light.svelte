<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhvuqubwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhvuqubwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:psitransfer-light" {...props}></Icon>
