<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8sbembrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8sbembrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:polygon" {...props}></Icon>
