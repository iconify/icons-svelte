<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd50wmpdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sd50wmpdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:itunes-note" {...props}></Icon>
