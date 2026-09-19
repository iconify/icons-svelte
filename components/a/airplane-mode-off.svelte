<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im7wiu58z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im7wiu58z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airplane-mode-off" {...props}></Icon>
