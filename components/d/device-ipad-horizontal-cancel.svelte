<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at4a6-b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at4a6-b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-cancel" {...props}></Icon>
