<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cncna5pxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cncna5pxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-matches" {...props}></Icon>
