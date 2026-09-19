<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4cr8yeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gz4cr8yeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-1-outline" {...props}></Icon>
