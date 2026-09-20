<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4m3nlfkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i4m3nlfkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:compress-arrows-alt-solid" {...props}></Icon>
