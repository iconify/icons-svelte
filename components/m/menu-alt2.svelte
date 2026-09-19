<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i25j6_12l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i25j6_12l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:menu-alt2" {...props}></Icon>
