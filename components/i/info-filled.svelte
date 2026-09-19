<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiyys2sek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xiyys2sek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:info-filled" {...props}></Icon>
