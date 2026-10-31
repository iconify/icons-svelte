<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9so2wdev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9so2wdev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-minus-corner-round" {...props}></Icon>
