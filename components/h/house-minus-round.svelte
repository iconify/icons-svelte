<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3y8rb7oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3y8rb7oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-minus-round" {...props}></Icon>
