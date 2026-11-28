<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqg93z-sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqg93z-sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:doorbell-solid" {...props}></Icon>
