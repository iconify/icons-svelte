<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt2audz9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt2audz9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:questdb-dark" {...props}></Icon>
