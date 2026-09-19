<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwauig-7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fwauig-7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rectangle-outline" {...props}></Icon>
