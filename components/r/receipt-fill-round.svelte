<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjat-_exd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjat-_exd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:receipt-fill-round" {...props}></Icon>
