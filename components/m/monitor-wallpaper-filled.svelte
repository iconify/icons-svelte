<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quypo_bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quypo_bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:monitor-wallpaper-filled" {...props}></Icon>
