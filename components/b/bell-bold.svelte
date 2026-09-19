<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-cn6l9zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b-cn6l9zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-bold" {...props}></Icon>
