<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8e4yyaeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8e4yyaeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:download-4" {...props}></Icon>
