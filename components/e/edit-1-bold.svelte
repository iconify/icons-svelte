<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp5oynpvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qp5oynpvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:edit-1-bold" {...props}></Icon>
