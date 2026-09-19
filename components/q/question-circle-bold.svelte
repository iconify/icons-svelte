<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1uvuf1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="df1uvuf1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:question-circle-bold" {...props}></Icon>
