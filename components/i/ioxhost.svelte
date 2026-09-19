<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3wsjtbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1664};
const content = `<path class="y3wsjtbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ioxhost" {...props}></Icon>
