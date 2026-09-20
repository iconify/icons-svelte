<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejmzit6-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejmzit6-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubernetes-light" {...props}></Icon>
