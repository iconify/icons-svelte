<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4nlpgpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ec4nlpgpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-duo" {...props}></Icon>
