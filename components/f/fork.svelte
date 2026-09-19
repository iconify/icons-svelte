<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8x1deb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8x1deb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fork" {...props}></Icon>
