<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-5yzob-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l-5yzob-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microphone-2-outline" {...props}></Icon>
