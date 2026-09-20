<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw6n93ogd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw6n93ogd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:inbox-all" {...props}></Icon>
