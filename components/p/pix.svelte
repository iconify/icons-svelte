<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heyvw_7vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heyvw_7vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pix" {...props}></Icon>
