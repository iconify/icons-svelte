<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j32p94i6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j32p94i6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-plus" {...props}></Icon>
