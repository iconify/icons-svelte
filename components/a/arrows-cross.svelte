<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcj7d6fkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lcj7d6fkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-cross" {...props}></Icon>
