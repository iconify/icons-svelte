<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq--7gh0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq--7gh0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:responsive-design-bold" {...props}></Icon>
