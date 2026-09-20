<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj4pe0big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":264.6,"height":255.6};
const content = `<path class="sj4pe0big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nestjs" {...props}></Icon>
