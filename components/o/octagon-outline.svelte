<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up3_59bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="up3_59bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:octagon-outline" {...props}></Icon>
