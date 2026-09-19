<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln1jp2beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1jp2beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:binoculars" {...props}></Icon>
