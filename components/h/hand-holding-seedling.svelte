<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgi2v4blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kgi2v4blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-seedling" {...props}></Icon>
