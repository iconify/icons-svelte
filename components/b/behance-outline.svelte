<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/c/c5u8khjtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="c5u8khjtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:behance-outline" {...props}></Icon>
