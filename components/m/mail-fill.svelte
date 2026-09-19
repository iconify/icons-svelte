<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5cs7qb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s5cs7qb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-fill" {...props}></Icon>
