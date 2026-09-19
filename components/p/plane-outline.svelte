<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9kdpbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="li9kdpbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-outline" {...props}></Icon>
