<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8a-znbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8a-znbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:courier-fast" {...props}></Icon>
