<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1uby1jjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z1uby1jjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:leaf-bold" {...props}></Icon>
