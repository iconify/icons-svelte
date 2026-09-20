<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shzgw1b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shzgw1b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-play-outline" {...props}></Icon>
