<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwz_shb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="iwz_shb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-items-center" {...props}></Icon>
