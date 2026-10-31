<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de_v7eb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de_v7eb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-n-bulk-round" {...props}></Icon>
