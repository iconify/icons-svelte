<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nggfwi-6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nggfwi-6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-u-round" {...props}></Icon>
