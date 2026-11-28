<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_k__0-_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_k__0-_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-star" {...props}></Icon>
