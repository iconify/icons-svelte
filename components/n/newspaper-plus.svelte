<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqi9hvm3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqi9hvm3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:newspaper-plus" {...props}></Icon>
