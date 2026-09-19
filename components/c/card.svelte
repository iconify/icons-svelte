<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utgju3_rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utgju3_rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:card" {...props}></Icon>
