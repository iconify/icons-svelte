<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn9ipccxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fn9ipccxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-reply-all-mirrored" {...props}></Icon>
