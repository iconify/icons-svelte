<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfk2zh8ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jfk2zh8ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:app-document-filled" {...props}></Icon>
