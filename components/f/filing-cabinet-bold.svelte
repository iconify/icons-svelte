<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o739jh8vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o739jh8vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:filing-cabinet-bold" {...props}></Icon>
