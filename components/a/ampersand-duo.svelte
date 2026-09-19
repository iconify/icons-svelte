<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf9onqh5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pf9onqh5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ampersand-duo" {...props}></Icon>
