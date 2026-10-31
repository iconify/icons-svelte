<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_hz9gztg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_hz9gztg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:forward-bulk-round" {...props}></Icon>
