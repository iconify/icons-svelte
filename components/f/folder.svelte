<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo30agb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xo30agb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder" {...props}></Icon>
