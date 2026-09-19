<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wa_q_fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h4wa_q_fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baby-bold" {...props}></Icon>
