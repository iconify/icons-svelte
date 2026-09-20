<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvh1ohb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvh1ohb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-pin" {...props}></Icon>
