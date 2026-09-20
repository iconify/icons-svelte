<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03xylb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w03xylb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:drop" {...props}></Icon>
