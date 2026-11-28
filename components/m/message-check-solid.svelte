<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymv6giefm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymv6giefm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-check-solid" {...props}></Icon>
