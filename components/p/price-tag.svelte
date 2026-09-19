<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_yuh5o2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g_yuh5o2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:price-tag" {...props}></Icon>
