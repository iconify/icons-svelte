<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvcqaccok.css';
import '../../css/j/jhhyfu85f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uvcqaccok"/><path class="jhhyfu85f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-books-2" {...props}></Icon>
