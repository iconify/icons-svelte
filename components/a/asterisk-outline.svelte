<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3_k9bchf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g3_k9bchf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:asterisk-outline" {...props}></Icon>
