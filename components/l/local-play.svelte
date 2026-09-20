<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sszfuucnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sszfuucnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-play" {...props}></Icon>
