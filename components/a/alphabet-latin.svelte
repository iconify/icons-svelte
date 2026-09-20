<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2gpywbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2gpywbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-latin" {...props}></Icon>
