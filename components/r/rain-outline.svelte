<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn9in6okr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nn9in6okr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rain-outline" {...props}></Icon>
