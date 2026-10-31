<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvy2xtale.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvy2xtale"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-more-vertical-round" {...props}></Icon>
