<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_84t1yuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f_84t1yuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-2-bold" {...props}></Icon>
