<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tysq3hb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="tysq3hb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:flickr" {...props}></Icon>
