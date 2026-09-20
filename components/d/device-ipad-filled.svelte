<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xopfsu1zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xopfsu1zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-filled" {...props}></Icon>
