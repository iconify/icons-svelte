<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj4hvkb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yj4hvkb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-web-services-dark" {...props}></Icon>
