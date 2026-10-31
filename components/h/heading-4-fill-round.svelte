<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4fgcfq9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4fgcfq9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-4-fill-round" {...props}></Icon>
