<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzi_4nscr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzi_4nscr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-acrobat" {...props}></Icon>
