<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9j1fm6fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="b9j1fm6fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:octagon-bold" {...props}></Icon>
