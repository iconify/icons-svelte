<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndg-id0tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ndg-id0tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:burger" {...props}></Icon>
