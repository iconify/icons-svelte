<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6l0acvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6l0acvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-3-2-fill-round" {...props}></Icon>
