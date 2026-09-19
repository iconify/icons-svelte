<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujchlhbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ujchlhbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:road-bold" {...props}></Icon>
