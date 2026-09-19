<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe09umb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fe09umb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-1-bold" {...props}></Icon>
