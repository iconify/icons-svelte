<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvpgfle6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvpgfle6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:firework-rocket-4" {...props}></Icon>
