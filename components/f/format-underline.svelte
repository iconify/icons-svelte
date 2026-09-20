<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn0m9xbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn0m9xbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-underline" {...props}></Icon>
