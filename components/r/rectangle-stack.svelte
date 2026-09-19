<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6sy5lsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hd6sy5lsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:rectangle-stack" {...props}></Icon>
