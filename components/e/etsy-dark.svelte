<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnv50rb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hnv50rb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etsy-dark" {...props}></Icon>
