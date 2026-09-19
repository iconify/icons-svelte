<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7o88uevm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7o88uevm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square" {...props}></Icon>
