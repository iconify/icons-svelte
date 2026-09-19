<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytkv-bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1179,"height":1000};
const content = `<path class="fytkv-bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:ok" {...props}></Icon>
