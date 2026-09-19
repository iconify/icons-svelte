<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmgfy0_4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qmgfy0_4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-slash-outline" {...props}></Icon>
