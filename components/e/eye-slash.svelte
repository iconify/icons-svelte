<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddw5uz2vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddw5uz2vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:eye-slash" {...props}></Icon>
