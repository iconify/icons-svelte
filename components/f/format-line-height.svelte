<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-cyhzb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cyhzb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-line-height" {...props}></Icon>
