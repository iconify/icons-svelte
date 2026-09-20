<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbr8hcbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pbr8hcbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:box-open-solid" {...props}></Icon>
