<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1jzv7brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c1jzv7brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-open-outline" {...props}></Icon>
