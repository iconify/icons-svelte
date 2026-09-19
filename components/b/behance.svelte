<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tav3z1unb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":830,"height":750};
const content = `<path class="tav3z1unb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:behance" {...props}></Icon>
