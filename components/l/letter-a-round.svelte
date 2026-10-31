<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sprkijbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sprkijbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-a-round" {...props}></Icon>
