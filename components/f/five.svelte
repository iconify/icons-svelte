<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzcg2bcvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yzcg2bcvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:five" {...props}></Icon>
