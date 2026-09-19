<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upp1jkb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="upp1jkb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-3-bold" {...props}></Icon>
