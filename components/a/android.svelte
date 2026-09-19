<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ecztt3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":520};
const content = `<path class="b2ecztt3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:android" {...props}></Icon>
