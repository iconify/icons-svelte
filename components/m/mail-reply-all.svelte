<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz2cm8bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oz2cm8bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-reply-all" {...props}></Icon>
