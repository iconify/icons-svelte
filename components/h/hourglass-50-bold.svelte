<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky4n3ccwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ky4n3ccwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-50-bold" {...props}></Icon>
