<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ts2wbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="i0ts2wbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hourglass-o" {...props}></Icon>
