<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldgncw1xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldgncw1xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-fill-round" {...props}></Icon>
