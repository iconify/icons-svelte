<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknxk9b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sknxk9b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-wireless" {...props}></Icon>
