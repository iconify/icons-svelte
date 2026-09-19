<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2osm-bfo.css';
import '../../css/w/wqbkv8u2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2osm-bfo"/><path class="wqbkv8u2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-help-circle" {...props}></Icon>
