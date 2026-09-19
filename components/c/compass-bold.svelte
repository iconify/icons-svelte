<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-g_txqbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v-g_txqbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:compass-bold" {...props}></Icon>
