<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfe0fh0ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfe0fh0ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-download-check" {...props}></Icon>
