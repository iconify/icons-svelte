<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl4bf3bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl4bf3bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:brush-filled" {...props}></Icon>
