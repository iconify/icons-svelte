<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id3zm3bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id3zm3bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-fill-round" {...props}></Icon>
