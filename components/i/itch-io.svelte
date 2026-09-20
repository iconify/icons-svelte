<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkg0_ibsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hkg0_ibsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:itch-io" {...props}></Icon>
