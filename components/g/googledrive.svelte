<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp8lvw4jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="jp8lvw4jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:googledrive" {...props}></Icon>
