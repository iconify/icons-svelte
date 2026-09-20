<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un8h6bb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un8h6bb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-gif-box" {...props}></Icon>
