<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu8vh-i6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu8vh-i6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:devices-pc-off" {...props}></Icon>
