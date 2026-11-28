<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ld7sxot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y3ld7sxot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-off-duotone" {...props}></Icon>
