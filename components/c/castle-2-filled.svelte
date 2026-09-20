<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ybo53nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ybo53nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-2-filled" {...props}></Icon>
