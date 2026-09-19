<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6rtj7bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y6rtj7bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-middle" {...props}></Icon>
