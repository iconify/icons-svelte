<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciisitb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ciisitb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:eleme-filled" {...props}></Icon>
