<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2p9d0b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2p9d0b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-info-fill" {...props}></Icon>
