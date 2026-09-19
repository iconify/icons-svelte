<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zessfchne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="zessfchne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dropbox" {...props}></Icon>
