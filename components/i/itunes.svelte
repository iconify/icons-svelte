<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsky5lzvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsky5lzvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:itunes" {...props}></Icon>
