<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf52njb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf52njb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-v-diamond-solid" {...props}></Icon>
