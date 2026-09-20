<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00jo0q8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f00jo0q8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dog-side-off" {...props}></Icon>
