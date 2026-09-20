<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irkc8bc8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irkc8bc8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-bold" {...props}></Icon>
