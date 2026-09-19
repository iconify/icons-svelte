<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hket147pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hket147pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laugh-wink-bold" {...props}></Icon>
