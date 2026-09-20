<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iltvxha0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iltvxha0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:loader" {...props}></Icon>
