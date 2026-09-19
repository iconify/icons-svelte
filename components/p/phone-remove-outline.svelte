<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo2hszohb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="oo2hszohb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-remove-outline" {...props}></Icon>
