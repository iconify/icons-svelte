<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-06-6rfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f-06-6rfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lifepreserver" {...props}></Icon>
