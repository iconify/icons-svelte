<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rugb_d0ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rugb_d0ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:archive-arrow-up" {...props}></Icon>
