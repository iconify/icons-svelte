<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2di10bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2di10bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:google-fill-round" {...props}></Icon>
