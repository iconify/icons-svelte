<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tze1n8bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":614};
const content = `<path class="tze1n8bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flickrthree" {...props}></Icon>
