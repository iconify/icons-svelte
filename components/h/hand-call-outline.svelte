<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_jv-6uof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n_jv-6uof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-call-outline" {...props}></Icon>
