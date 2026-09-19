<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zicf9cb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="zicf9cb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:filemanager" {...props}></Icon>
