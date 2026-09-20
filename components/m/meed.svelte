<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrkj0x3un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrkj0x3un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:meed" {...props}></Icon>
