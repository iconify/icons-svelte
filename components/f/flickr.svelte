<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1wjnncqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1wjnncqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:flickr" {...props}></Icon>
