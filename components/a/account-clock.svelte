<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chg7ycchf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chg7ycchf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-clock" {...props}></Icon>
