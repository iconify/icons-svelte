<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqi1sbb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eqi1sbb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:keycap-outline" {...props}></Icon>
