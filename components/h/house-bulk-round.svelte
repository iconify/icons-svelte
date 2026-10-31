<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp66z6jrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp66z6jrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-bulk-round" {...props}></Icon>
