<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i50hvfb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i50hvfb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:factory-filled" {...props}></Icon>
