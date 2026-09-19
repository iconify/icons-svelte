<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siypbytrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="siypbytrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:copy-2-outline" {...props}></Icon>
