<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b71fi303z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b71fi303z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gifts" {...props}></Icon>
