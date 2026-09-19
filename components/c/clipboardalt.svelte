<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9l5b2b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="x9l5b2b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clipboardalt" {...props}></Icon>
