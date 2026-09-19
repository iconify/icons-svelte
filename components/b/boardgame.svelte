<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqtmd9bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="xqtmd9bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:boardgame" {...props}></Icon>
