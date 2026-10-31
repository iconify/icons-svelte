<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2am-7b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2am-7b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-more-vertical-fill-round" {...props}></Icon>
