<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgrr9qb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgrr9qb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:repeat-1-sharp" {...props}></Icon>
