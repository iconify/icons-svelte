<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sofd8nbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sofd8nbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-sm" {...props}></Icon>
