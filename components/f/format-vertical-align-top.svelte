<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifrgh_bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifrgh_bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-vertical-align-top" {...props}></Icon>
