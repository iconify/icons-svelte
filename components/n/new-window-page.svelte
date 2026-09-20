<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frp_v-l8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frp_v-l8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:new-window-page" {...props}></Icon>
