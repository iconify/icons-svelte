<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw8pzqbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nw8pzqbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikivoyage" {...props}></Icon>
