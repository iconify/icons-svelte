<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlzd5tbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlzd5tbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:antora-light" {...props}></Icon>
