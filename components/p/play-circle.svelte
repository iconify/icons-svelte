<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2ahxob9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="f2ahxob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:play-circle" {...props}></Icon>
