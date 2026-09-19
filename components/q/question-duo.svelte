<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wte0abq2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wte0abq2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:question-duo" {...props}></Icon>
