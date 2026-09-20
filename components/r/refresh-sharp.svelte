<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-pxa7trs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-pxa7trs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:refresh-sharp" {...props}></Icon>
