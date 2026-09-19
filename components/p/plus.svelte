<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntat1nopg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ntat1nopg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plus" {...props}></Icon>
