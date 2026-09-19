<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vij84ybpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vij84ybpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attachment-thin" {...props}></Icon>
