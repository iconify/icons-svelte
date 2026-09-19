<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-6j9z3rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f-6j9z3rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-1-bold" {...props}></Icon>
