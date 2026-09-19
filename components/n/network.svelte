<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdgvcgq-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hdgvcgq-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:network" {...props}></Icon>
