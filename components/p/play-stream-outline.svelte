<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pokd3xc_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pokd3xc_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-stream-outline" {...props}></Icon>
