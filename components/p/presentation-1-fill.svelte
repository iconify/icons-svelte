<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ib-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ib-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-1-fill" {...props}></Icon>
