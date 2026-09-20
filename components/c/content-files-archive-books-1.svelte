<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjxlhlb8t.css';
import '../../css/s/sv5erwbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qjxlhlb8t"/><path class="sv5erwbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-archive-books-1" {...props}></Icon>
