<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl3udhkbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl3udhkbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:barrel" {...props}></Icon>
