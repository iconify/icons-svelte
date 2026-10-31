<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz8e6p2tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz8e6p2tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-plus-fill-round" {...props}></Icon>
