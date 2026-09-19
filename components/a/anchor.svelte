<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la-n7dbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="la-n7dbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:anchor" {...props}></Icon>
