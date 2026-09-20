<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcpc46bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcpc46bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive" {...props}></Icon>
