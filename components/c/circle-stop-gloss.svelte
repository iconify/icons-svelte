<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a91wexbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a91wexbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-stop-gloss" {...props}></Icon>
