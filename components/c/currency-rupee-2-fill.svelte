<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn11p7b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn11p7b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-2-fill" {...props}></Icon>
