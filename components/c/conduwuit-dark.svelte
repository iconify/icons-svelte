<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szu_-8m4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="szu_-8m4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conduwuit-dark" {...props}></Icon>
