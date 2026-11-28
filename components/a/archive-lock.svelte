<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaztl-eah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaztl-eah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:archive-lock" {...props}></Icon>
