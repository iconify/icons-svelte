<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7sprub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7sprub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:flag-thin" {...props}></Icon>
