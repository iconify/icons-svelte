<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoj4kmq1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uoj4kmq1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-note-book" {...props}></Icon>
