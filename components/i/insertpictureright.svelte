<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxo7lob4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="xxo7lob4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:insertpictureright" {...props}></Icon>
