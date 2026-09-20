<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tni8dxx4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tni8dxx4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:duplicate" {...props}></Icon>
