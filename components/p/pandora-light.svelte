<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap-vx6b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ap-vx6b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pandora-light" {...props}></Icon>
