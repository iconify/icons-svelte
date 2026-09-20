<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbho9sbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbho9sbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-square-line" {...props}></Icon>
