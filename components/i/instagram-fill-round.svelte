<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syikrlqkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syikrlqkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:instagram-fill-round" {...props}></Icon>
