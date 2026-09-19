<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze1sy3buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ze1sy3buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:minus-bold" {...props}></Icon>
