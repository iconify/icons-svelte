<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhgko-bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhgko-bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinepods-dark" {...props}></Icon>
