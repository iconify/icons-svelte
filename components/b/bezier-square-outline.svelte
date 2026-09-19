<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb7v0vb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nb7v0vb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-square-outline" {...props}></Icon>
