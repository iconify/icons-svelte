<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_wmkzbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z_wmkzbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-horns-bold" {...props}></Icon>
