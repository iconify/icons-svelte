<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qclasgpbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qclasgpbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pause-circle-bold" {...props}></Icon>
