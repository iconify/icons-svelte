<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-vrd-b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-vrd-b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pastebin" {...props}></Icon>
