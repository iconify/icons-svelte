<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwg2vsr1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwg2vsr1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-open-alt-filled" {...props}></Icon>
