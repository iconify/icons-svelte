<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiqe1-61x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":820};
const content = `<path class="wiqe1-61x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:comment" {...props}></Icon>
