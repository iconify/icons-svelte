<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk-3pyb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uk-3pyb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:badge-duo" {...props}></Icon>
