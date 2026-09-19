<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk352rb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bk352rb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-bold" {...props}></Icon>
