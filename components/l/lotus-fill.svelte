<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqlc8-b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqlc8-b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lotus-fill" {...props}></Icon>
