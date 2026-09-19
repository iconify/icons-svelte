<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ud-2ngi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="x3ud-2ngi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:play-circle-o" {...props}></Icon>
