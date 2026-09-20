<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/donl33jro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="donl33jro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emby" {...props}></Icon>
