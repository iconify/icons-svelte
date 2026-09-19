<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay1xdy5oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="ay1xdy5oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mail-reply-all" {...props}></Icon>
