<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kng6abcjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kng6abcjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3" {...props}></Icon>
