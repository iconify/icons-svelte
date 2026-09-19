<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pum6gtbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="pum6gtbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:language-javascript" {...props}></Icon>
