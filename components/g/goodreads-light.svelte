<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldh1zzbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ldh1zzbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goodreads-light" {...props}></Icon>
