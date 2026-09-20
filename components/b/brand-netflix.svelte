<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1d2yybis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1d2yybis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-netflix" {...props}></Icon>
