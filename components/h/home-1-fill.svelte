<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec3i1xbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec3i1xbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-1-fill" {...props}></Icon>
