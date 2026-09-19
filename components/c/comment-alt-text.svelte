<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk6vsqjki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="pk6vsqjki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-alt-text" {...props}></Icon>
