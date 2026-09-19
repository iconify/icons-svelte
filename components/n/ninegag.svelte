<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwk8hfbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="qwk8hfbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ninegag" {...props}></Icon>
