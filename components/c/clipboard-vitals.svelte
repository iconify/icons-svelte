<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un_ni6bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un_ni6bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-vitals" {...props}></Icon>
