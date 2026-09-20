<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdb3384up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdb3384up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-list-2-line" {...props}></Icon>
