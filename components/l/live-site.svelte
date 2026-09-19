<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3g14o-3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d3g14o-3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:live-site" {...props}></Icon>
