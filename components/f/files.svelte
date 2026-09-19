<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrc1gib8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zrc1gib8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:files" {...props}></Icon>
