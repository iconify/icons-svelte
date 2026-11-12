<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmy7jtbal.css';
import '../../css/u/u01dg9zki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmy7jtbal"/><path class="u01dg9zki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chatgpt" {...props}></Icon>
