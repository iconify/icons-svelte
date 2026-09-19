<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ful54ccld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ful54ccld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-lightroom-classic" {...props}></Icon>
